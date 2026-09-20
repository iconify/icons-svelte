<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewhgnkbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ewhgnkbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:folder-open-16" {...props}></Icon>
