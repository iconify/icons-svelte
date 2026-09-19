<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdvwsbako.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xdvwsbako"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:jest" {...props}></Icon>
