<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujk5wwbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ujk5wwbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:monument" {...props}></Icon>
