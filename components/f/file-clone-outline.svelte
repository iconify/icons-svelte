<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di935-bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di935-bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-clone-outline" {...props}></Icon>
