<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpqhfeb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpqhfeb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:puzzle-favorite" {...props}></Icon>
