<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xonpi7osi.css';
import '../../css/i/ib8s1i8wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xonpi7osi"/><path class="ib8s1i8wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-gitea" {...props}></Icon>
