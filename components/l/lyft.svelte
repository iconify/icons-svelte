<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0un1ccyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b0un1ccyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:lyft" {...props}></Icon>
