<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p35pwcbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="p35pwcbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:google-scholar" {...props}></Icon>
