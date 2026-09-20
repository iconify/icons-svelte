<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdf8a4bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdf8a4bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:corner-left-up" {...props}></Icon>
