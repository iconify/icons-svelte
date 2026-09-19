<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efkcvgvnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efkcvgvnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:equal-filled" {...props}></Icon>
