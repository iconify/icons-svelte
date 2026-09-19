<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_nktbacs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a_nktbacs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chrome-minimize" {...props}></Icon>
