<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbw2nob3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbw2nob3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dna-fill" {...props}></Icon>
