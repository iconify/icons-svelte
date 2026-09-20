<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klsc_6f6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="klsc_6f6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrows-left-right" {...props}></Icon>
