<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djm0w-btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djm0w-btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-right-through-line-solid" {...props}></Icon>
