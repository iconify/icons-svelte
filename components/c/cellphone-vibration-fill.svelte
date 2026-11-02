<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyu8w6b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyu8w6b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cellphone-vibration-fill" {...props}></Icon>
