<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnre6hb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dnre6hb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:person-run" {...props}></Icon>
