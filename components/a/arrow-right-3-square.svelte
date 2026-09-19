<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksotj3byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksotj3byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-3-square" {...props}></Icon>
