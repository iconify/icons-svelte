<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayh6ug0lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ayh6ug0lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hamsa" {...props}></Icon>
