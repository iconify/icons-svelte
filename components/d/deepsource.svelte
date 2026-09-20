<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7veribva.css';
import '../../css/b/bpjvsabdv.css';
import '../../css/k/koxyqebxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g7veribva"/><path class="bpjvsabdv"/><path class="koxyqebxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:deepsource" {...props}></Icon>
