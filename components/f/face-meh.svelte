<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i20o1k74r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i20o1k74r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:face-meh" {...props}></Icon>
