<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rrnwx6buh.css';
import '../../css/p/pr3cdbb2n.css';
import '../../css/e/ejdkgccas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rrnwx6buh"/><path class="pr3cdbb2n"/><path class="ejdkgccas"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-line-broken" {...props}></Icon>
