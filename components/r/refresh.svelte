<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htym47wlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="htym47wlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:refresh" {...props}></Icon>
