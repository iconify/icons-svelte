<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-v7-ebrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f-v7-ebrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:play-btn-fill" {...props}></Icon>
