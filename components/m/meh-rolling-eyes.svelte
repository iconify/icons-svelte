<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6urbrbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z6urbrbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:meh-rolling-eyes" {...props}></Icon>
