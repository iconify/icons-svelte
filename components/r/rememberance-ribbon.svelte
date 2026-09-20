<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt9m3043v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lt9m3043v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rememberance-ribbon" {...props}></Icon>
