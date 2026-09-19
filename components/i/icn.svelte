<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7xhl_bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k7xhl_bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:icn" {...props}></Icon>
