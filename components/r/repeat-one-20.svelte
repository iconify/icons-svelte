<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7bfszaos.css';
import '../../css/t/tbg_x-bdw.css';
import '../../css/s/sux4gdc6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k7bfszaos"/><path class="tbg_x-bdw"/><path class="sux4gdc6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:repeat-one-20" {...props}></Icon>
