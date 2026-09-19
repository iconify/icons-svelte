<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc6clzbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="tc6clzbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:dblp-square" {...props}></Icon>
