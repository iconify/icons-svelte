<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt_4t3wrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zt_4t3wrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:icx" {...props}></Icon>
