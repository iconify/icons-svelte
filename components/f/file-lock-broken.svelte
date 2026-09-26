<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t-dkfybbn.css';
import '../../css/f/fu0hrlguj.css';
import '../../css/t/t4qaumccy.css';
import '../../css/e/e0cmz0boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t-dkfybbn"/><path class="fu0hrlguj"/><path class="t4qaumccy"/><path class="e0cmz0boh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-lock-broken" {...props}></Icon>
