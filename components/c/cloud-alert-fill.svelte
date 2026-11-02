<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpv00lbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpv00lbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-alert-fill" {...props}></Icon>
