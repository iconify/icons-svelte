<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv77kib4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pv77kib4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:notes-12" {...props}></Icon>
