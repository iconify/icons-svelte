<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2w7s7nlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v2w7s7nlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:antibody" {...props}></Icon>
