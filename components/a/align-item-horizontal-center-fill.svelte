<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-zv1rukz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-zv1rukz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-item-horizontal-center-fill" {...props}></Icon>
