<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3pvdub4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h3pvdub4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:d20" {...props}></Icon>
