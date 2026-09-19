<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nky12llmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nky12llmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:art" {...props}></Icon>
