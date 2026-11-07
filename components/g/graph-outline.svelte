<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6_co0ppv.css';
import '../../css/t/t5k-_f5ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6_co0ppv"/><path clip-rule="evenodd" class="t5k-_f5ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:graph-outline" {...props}></Icon>
