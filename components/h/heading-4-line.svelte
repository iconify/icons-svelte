<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xerf8cb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xerf8cb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-4-line" {...props}></Icon>
