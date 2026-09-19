<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag4y0ib0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ag4y0ib0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:radioactive" {...props}></Icon>
