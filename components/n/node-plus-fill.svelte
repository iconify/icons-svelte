<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu640dmwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mu640dmwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:node-plus-fill" {...props}></Icon>
