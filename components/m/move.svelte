<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4dy5ebqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k4dy5ebqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:move" {...props}></Icon>
