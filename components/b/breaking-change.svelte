<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnij756ni.css';
import '../../css/s/sz1mxmeui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jnij756ni"/><path class="sz1mxmeui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:breaking-change" {...props}></Icon>
