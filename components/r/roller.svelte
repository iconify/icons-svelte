<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu_yqmbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":432};
const content = `<path class="zu_yqmbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:roller" {...props}></Icon>
