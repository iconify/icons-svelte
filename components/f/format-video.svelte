<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_t083bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o_t083bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:format-video" {...props}></Icon>
