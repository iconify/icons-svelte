<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9ohq6b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n9ohq6b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:magnifying-glass" {...props}></Icon>
