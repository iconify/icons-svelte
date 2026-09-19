<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5enlybph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d5enlybph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:basket2-fill" {...props}></Icon>
