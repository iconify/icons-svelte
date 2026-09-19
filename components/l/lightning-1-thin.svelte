<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_ar8bgky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_ar8bgky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lightning-1-thin" {...props}></Icon>
