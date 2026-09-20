<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn30zibei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gn30zibei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-open-book" {...props}></Icon>
