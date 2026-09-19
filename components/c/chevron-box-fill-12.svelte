<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxl5vd-_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hxl5vd-_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-box-fill-12" {...props}></Icon>
