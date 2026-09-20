<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz2qli0dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oz2qli0dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mars-double-solid" {...props}></Icon>
