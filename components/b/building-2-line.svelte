<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqh3i2bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqh3i2bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-2-line" {...props}></Icon>
