<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u34u9o27z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u34u9o27z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calculator-fill" {...props}></Icon>
