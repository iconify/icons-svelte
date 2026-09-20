<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcks5cuuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mcks5cuuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:credit-card-approved" {...props}></Icon>
