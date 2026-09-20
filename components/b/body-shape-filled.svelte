<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo0he1bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo0he1bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:body-shape-filled" {...props}></Icon>
