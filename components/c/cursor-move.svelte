<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf9m077hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf9m077hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:cursor-move" {...props}></Icon>
