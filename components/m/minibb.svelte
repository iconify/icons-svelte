<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry_3st_jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ry_3st_jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:minibb" {...props}></Icon>
