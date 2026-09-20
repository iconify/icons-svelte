<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2u_3tbje.css';
import '../../css/z/znxwd8tvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="s2u_3tbje"/><path class="znxwd8tvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:imaging-root-category" {...props}></Icon>
