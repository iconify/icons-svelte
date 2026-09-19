<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot5cy7qnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ot5cy7qnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:indent-increase-stroke-12" {...props}></Icon>
