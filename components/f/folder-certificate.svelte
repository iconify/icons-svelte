<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9jj03bpd.css';
import '../../css/x/xwlvzbvrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m9jj03bpd"/><path class="xwlvzbvrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-certificate" {...props}></Icon>
