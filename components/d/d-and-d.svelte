<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b67ejim3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="b67ejim3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:d-and-d" {...props}></Icon>
