<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrpi9pbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrpi9pbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:facebook-fill" {...props}></Icon>
