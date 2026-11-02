<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpp256gqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpp256gqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:greatwall-fill" {...props}></Icon>
