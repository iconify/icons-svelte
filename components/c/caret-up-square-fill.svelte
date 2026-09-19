<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0yx3epbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m0yx3epbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:caret-up-square-fill" {...props}></Icon>
