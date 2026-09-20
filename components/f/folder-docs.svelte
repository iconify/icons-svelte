<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcjmcxbsc.css';
import '../../css/x/xtenr_bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hcjmcxbsc"/><path class="xtenr_bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-docs" {...props}></Icon>
