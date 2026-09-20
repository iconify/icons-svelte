<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdlpnnk8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pdlpnnk8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:format-bold" {...props}></Icon>
