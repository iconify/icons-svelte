<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwlglobjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jwlglobjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bomb" {...props}></Icon>
