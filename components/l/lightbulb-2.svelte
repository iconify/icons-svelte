<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbb2bw7jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lbb2bw7jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lightbulb-2" {...props}></Icon>
