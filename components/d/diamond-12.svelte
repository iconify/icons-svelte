<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we4_k1bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="we4_k1bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:diamond-12" {...props}></Icon>
