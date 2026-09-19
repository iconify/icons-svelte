<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j58uu9b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="j58uu9b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:previous" {...props}></Icon>
