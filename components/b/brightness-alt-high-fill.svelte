<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcjhfdxlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jcjhfdxlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:brightness-alt-high-fill" {...props}></Icon>
