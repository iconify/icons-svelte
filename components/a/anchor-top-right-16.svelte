<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf_1fb-pf.css';
import '../../css/p/po8eo_bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qf_1fb-pf"/><path class="po8eo_bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:anchor-top-right-16" {...props}></Icon>
