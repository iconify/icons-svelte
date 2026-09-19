<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt-_c9tsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wt-_c9tsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:envelope" {...props}></Icon>
