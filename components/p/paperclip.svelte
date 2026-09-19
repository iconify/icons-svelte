<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g49kx7b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g49kx7b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:paperclip" {...props}></Icon>
