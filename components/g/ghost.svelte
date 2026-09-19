<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfpjjcc0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="pfpjjcc0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ghost" {...props}></Icon>
