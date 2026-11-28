<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma6ps_buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma6ps_buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:chef-hat" {...props}></Icon>
