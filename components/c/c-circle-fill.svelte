<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9_5x1_iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t9_5x1_iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:c-circle-fill" {...props}></Icon>
