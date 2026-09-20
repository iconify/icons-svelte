<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsmj48bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsmj48bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:castorama" {...props}></Icon>
