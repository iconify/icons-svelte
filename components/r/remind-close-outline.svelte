<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlg21pbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dlg21pbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:remind-close-outline" {...props}></Icon>
