<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4rj83b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4rj83b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dinner-fill" {...props}></Icon>
