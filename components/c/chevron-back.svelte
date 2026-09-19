<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urgutvb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="urgutvb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chevron-back" {...props}></Icon>
