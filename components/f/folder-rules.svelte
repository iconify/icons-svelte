<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f95-ijf-n.css';
import '../../css/n/nb5nokbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f95-ijf-n"/><path class="nb5nokbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-rules" {...props}></Icon>
