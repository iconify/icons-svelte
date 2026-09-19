<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp0e_-bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rp0e_-bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fliphorizontal" {...props}></Icon>
