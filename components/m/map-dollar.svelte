<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tolt5rb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tolt5rb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-dollar" {...props}></Icon>
