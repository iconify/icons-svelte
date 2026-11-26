<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqae2abwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqae2abwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:homey" {...props}></Icon>
