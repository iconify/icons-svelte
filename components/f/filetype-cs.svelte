<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7l4nmb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o7l4nmb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-cs" {...props}></Icon>
