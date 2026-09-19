<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj0zef79h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dj0zef79h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:rewind" {...props}></Icon>
