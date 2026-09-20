<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv2nmoqxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qv2nmoqxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:collapse-up" {...props}></Icon>
