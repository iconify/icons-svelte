<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz53detga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jz53detga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:heartbreak" {...props}></Icon>
