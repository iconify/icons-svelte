<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhtqtnb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mhtqtnb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:circle-filled-32" {...props}></Icon>
