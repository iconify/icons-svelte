<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa3gd9xnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wa3gd9xnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:heading" {...props}></Icon>
