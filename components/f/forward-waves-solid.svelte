<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpn8occcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpn8occcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:forward-waves-solid" {...props}></Icon>
