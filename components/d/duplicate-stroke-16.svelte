<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9l492b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m9l492b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:duplicate-stroke-16" {...props}></Icon>
