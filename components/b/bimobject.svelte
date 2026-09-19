<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke5p-6bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ke5p-6bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:bimobject" {...props}></Icon>
