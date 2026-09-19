<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1kskccyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z1kskccyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:octagon-half" {...props}></Icon>
