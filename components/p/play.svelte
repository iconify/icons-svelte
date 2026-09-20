<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0kk_sbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="z0kk_sbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:play" {...props}></Icon>
