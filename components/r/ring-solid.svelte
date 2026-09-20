<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0i8p3mks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d0i8p3mks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ring-solid" {...props}></Icon>
