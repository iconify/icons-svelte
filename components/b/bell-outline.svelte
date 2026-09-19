<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xto9lgpmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xto9lgpmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:bell-outline" {...props}></Icon>
