<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzt3mey7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fzt3mey7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:globe-americas-outline" {...props}></Icon>
