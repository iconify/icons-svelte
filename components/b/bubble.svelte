<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id5hbu2ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":496};
const content = `<path class="id5hbu2ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:bubble" {...props}></Icon>
