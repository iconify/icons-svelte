<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvk_-kegd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kvk_-kegd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:audio-description" {...props}></Icon>
