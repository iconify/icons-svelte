<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glp2bkbii.css';
import '../../css/m/mynrssntn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="glp2bkbii"/><path class="mynrssntn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chat-bot" {...props}></Icon>
