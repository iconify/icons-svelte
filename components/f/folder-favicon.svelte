<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7n2shh1v.css';
import '../../css/v/vq1grpt4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p7n2shh1v"/><path class="vq1grpt4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-favicon" {...props}></Icon>
