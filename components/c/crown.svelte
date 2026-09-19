<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh5pykbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="yh5pykbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:crown" {...props}></Icon>
