<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye_oo_m6x.css';
import '../../css/a/ab89kobbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye_oo_m6x"/><path class="ab89kobbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:photo-album" {...props}></Icon>
