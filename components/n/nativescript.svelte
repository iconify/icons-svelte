<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9zamdlpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p9zamdlpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:nativescript" {...props}></Icon>
