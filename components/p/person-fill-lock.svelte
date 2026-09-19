<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz8o_0b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bz8o_0b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:person-fill-lock" {...props}></Icon>
