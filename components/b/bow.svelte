<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7ellybvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="t7ellybvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:bow" {...props}></Icon>
