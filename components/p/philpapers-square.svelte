<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns0ymobwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ns0ymobwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:philpapers-square" {...props}></Icon>
