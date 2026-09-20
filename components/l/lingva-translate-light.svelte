<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9lhmib8f.css';
import '../../css/d/d_cc7c6xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m9lhmib8f"/><path class="d_cc7c6xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lingva-translate-light" {...props}></Icon>
