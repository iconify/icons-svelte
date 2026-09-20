<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwm-ibb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwm-ibb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:augmented-reality" {...props}></Icon>
