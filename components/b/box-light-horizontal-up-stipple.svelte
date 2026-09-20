<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm5iofbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hm5iofbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-up-stipple" {...props}></Icon>
