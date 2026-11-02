<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_7rh19xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_7rh19xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leafy-green-line" {...props}></Icon>
