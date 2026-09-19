<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx3o0m84v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mx3o0m84v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:magnet" {...props}></Icon>
