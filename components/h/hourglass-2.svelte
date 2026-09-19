<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd-rz_mmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="rd-rz_mmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hourglass-2" {...props}></Icon>
