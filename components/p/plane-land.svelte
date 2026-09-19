<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc3hafbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc3hafbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:plane-land" {...props}></Icon>
