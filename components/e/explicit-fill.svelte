<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blt9k2ogm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="blt9k2ogm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:explicit-fill" {...props}></Icon>
