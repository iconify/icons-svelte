<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw-pwm7xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="sw-pwm7xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gsm3" {...props}></Icon>
