<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0u_4izij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="v0u_4izij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:banana" {...props}></Icon>
