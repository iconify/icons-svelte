<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vctk-r6se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vctk-r6se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:multiply-square" {...props}></Icon>
