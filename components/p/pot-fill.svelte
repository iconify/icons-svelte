<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfzvn7btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfzvn7btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pot-fill" {...props}></Icon>
