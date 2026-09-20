<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jky5v_bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jky5v_bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:cloud-offline-16" {...props}></Icon>
