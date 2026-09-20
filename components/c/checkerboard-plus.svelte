<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo_bad7tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo_bad7tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkerboard-plus" {...props}></Icon>
