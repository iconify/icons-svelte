<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jccwzwjwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jccwzwjwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:gem" {...props}></Icon>
