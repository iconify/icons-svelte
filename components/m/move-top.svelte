<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f8yqsxb0s.css';
import '../../css/s/syhyksbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle transform="matrix(0 -1 -1 0 15 22)" class="f8yqsxb0s"/><path class="syhyksbpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:move-top" {...props}></Icon>
