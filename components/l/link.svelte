<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni6r_2b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ni6r_2b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:link" {...props}></Icon>
