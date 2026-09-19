<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jin3rs3na.css';
import '../../css/p/pd26jybbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jin3rs3na"/><path class="pd26jybbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:football" {...props}></Icon>
