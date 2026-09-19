<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujlo24bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ujlo24bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cursor-arrow-stroke-12" {...props}></Icon>
