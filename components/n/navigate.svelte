<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzjpee4cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uzjpee4cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:navigate" {...props}></Icon>
