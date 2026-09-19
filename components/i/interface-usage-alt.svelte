<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_1vk6bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k_1vk6bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:interface-usage-alt" {...props}></Icon>
