<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqbzzaccj.css';
import '../../css/x/xhcfzkbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sqbzzaccj"/><path class="xhcfzkbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:firewall" {...props}></Icon>
