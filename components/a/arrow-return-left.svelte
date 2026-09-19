<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vndlk5bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vndlk5bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-return-left" {...props}></Icon>
