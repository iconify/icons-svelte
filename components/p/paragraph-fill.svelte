<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrfmp86ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrfmp86ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paragraph-fill" {...props}></Icon>
