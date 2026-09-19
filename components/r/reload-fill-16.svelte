<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osur7d7zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="osur7d7zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:reload-fill-16" {...props}></Icon>
