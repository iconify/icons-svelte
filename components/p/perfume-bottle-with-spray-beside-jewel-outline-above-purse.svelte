<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo8k2rb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jo8k2rb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:perfume-bottle-with-spray-beside-jewel-outline-above-purse" {...props}></Icon>
