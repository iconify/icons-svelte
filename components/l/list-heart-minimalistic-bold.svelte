<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqtyd2syu.css';
import '../../css/t/tzom42bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqtyd2syu"/><path class="tzom42bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-heart-minimalistic-bold" {...props}></Icon>
