<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzbu0ndxo.css';
import '../../css/z/zdzqfvyfv.css';
import '../../css/r/r5j29ko6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nzbu0ndxo"/><path class="zdzqfvyfv"/><path class="r5j29ko6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crib-20" {...props}></Icon>
