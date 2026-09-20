<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5zd7xsej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l5zd7xsej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:anguished-face-with-spots" {...props}></Icon>
