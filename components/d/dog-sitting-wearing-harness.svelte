<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-smipu6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p-smipu6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-sitting-wearing-harness" {...props}></Icon>
