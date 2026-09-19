<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzbn288cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gzbn288cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:note-double" {...props}></Icon>
