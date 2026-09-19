<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liyik2b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="liyik2b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:mnz" {...props}></Icon>
