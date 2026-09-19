<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9yr7ib5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9yr7ib5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mqttx" {...props}></Icon>
