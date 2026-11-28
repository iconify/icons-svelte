<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5o0gccin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5o0gccin primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dna-duotone" {...props}></Icon>
