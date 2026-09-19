<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od5gywd6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="od5gywd6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:rotate-clockwise" {...props}></Icon>
