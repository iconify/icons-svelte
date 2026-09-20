<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_c9h_pwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_c9h_pwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:clipboard-sharp" {...props}></Icon>
