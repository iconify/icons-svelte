<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcznrtbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xcznrtbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:4-circle-fill" {...props}></Icon>
