<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc-276b-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc-276b-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layers-plus" {...props}></Icon>
