<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugr3mblsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ugr3mblsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:face-satisfied-filled" {...props}></Icon>
