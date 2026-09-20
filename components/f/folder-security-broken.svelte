<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qw0rhm64r.css';
import '../../css/r/rkxx7jn-k.css';
import '../../css/i/i4dcgmbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="qw0rhm64r"/><path class="rkxx7jn-k"/><path class="i4dcgmbin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-security-broken" {...props}></Icon>
