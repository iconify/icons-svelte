<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toqre_blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="toqre_blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:page-break" {...props}></Icon>
