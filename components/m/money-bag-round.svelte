<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z39q21b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z39q21b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:money-bag-round" {...props}></Icon>
