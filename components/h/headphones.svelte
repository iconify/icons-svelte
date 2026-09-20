<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtybyow4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dtybyow4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:headphones" {...props}></Icon>
