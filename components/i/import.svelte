<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmwn0h9_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmwn0h9_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:import" {...props}></Icon>
