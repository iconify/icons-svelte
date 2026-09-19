<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlzbi5xzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlzbi5xzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:google" {...props}></Icon>
