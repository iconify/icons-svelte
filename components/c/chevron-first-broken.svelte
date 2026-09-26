<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nzhoqcmml.css';
import '../../css/v/v9gqdsvmm.css';
import '../../css/c/cfxd4se9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nzhoqcmml"/><path class="v9gqdsvmm"/><path class="cfxd4se9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevron-first-broken" {...props}></Icon>
