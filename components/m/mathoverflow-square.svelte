<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ne6hg34qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ne6hg34qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:mathoverflow-square" {...props}></Icon>
