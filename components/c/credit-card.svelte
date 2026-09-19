<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvhch1-4t.css';
import '../../css/o/oirzc_rey.css';
import '../../css/y/y3t9q1bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvhch1-4t"/><path class="oirzc_rey"/><path class="y3t9q1bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:credit-card" {...props}></Icon>
