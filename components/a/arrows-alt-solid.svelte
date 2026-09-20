<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3f3cdbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c3f3cdbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrows-alt-solid" {...props}></Icon>
