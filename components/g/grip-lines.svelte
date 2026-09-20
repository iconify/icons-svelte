<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y21owvl3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y21owvl3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:grip-lines" {...props}></Icon>
