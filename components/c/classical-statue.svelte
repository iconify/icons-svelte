<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj6w53b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wj6w53b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:classical-statue" {...props}></Icon>
