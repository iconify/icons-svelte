<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phsvk3hda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="phsvk3hda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:lock" {...props}></Icon>
