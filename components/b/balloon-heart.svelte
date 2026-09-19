<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joh4lsb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="joh4lsb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:balloon-heart" {...props}></Icon>
