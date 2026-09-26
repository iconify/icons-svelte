<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e0cmz0boh.css';
import '../../css/t/tvwvv6hyt.css';
import '../../css/v/vve12wqxb.css';
import '../../css/t/t4qaumccy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e0cmz0boh"/><circle class="tvwvv6hyt"/><path class="vve12wqxb"/><path class="t4qaumccy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-user-broken" {...props}></Icon>
