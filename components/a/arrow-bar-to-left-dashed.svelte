<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcez2jbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcez2jbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-bar-to-left-dashed" {...props}></Icon>
