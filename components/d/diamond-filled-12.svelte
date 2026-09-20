<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mojhw-3qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mojhw-3qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:diamond-filled-12" {...props}></Icon>
