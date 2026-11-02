<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veeb6g1ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veeb6g1ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:beer-fill" {...props}></Icon>
