<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggfa1pbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggfa1pbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-out-control-point-fill" {...props}></Icon>
