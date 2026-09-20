<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd6wl4g4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd6wl4g4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mouse-fill" {...props}></Icon>
