<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c73jr0ixh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="c73jr0ixh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:autoprefixer" {...props}></Icon>
