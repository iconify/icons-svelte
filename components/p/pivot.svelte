<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icbxjkx4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="icbxjkx4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pivot" {...props}></Icon>
