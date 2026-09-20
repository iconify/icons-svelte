<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axuu_poku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="axuu_poku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:border-outer" {...props}></Icon>
