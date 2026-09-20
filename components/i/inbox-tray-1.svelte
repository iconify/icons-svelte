<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvnprs7bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xvnprs7bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:inbox-tray-1" {...props}></Icon>
