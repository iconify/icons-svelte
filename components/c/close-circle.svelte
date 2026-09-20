<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd9y8ubqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd9y8ubqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:close-circle" {...props}></Icon>
