<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff7b9fi-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="ff7b9fi-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:card" {...props}></Icon>
