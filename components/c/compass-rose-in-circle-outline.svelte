<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soayfe2qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="soayfe2qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:compass-rose-in-circle-outline" {...props}></Icon>
