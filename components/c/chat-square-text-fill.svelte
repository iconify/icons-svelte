<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5e567fow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i5e567fow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-square-text-fill" {...props}></Icon>
