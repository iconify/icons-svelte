<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s92032bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s92032bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chevron-up-compact" {...props}></Icon>
