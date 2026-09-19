<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwr2e0b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="jwr2e0b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:quote" {...props}></Icon>
