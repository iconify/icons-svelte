<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bwx6lbcne.css';
import '../../css/b/b0hlurj5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect transform="matrix(0 -1 -1 0 22 21)" class="bwx6lbcne"/><rect transform="matrix(0 -1 -1 0 7 15.5)" class="bwx6lbcne"/><rect transform="matrix(0 -1 -1 0 22 10)" class="bwx6lbcne"/><path class="b0hlurj5v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:network-right" {...props}></Icon>
