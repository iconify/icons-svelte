<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of-f3g3uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of-f3g3uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:presentation-3-line" {...props}></Icon>
