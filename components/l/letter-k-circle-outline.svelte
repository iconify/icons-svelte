<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnq2lebro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnq2lebro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-k-circle-outline" {...props}></Icon>
