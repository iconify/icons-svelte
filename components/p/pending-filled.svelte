<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr72fibsk.css';
import '../../css/v/v3y0e9ubk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yr72fibsk"/><path class="v3y0e9ubk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pending-filled" {...props}></Icon>
