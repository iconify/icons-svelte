<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkmq8ioen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkmq8ioen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:aperture-sharp" {...props}></Icon>
