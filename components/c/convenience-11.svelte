<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkkij013w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="fkkij013w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:convenience-11" {...props}></Icon>
