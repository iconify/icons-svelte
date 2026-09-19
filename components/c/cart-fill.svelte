<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nggkwabds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nggkwabds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cart-fill" {...props}></Icon>
