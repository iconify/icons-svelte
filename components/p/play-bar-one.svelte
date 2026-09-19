<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu6qonbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu6qonbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:play-bar-one" {...props}></Icon>
