<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whz263bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="whz263bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:enj" {...props}></Icon>
