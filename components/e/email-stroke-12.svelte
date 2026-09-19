<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8pp2tbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="u8pp2tbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:email-stroke-12" {...props}></Icon>
