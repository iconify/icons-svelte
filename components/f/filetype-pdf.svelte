<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otla8nb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="otla8nb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-pdf" {...props}></Icon>
