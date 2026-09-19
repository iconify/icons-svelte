<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwm-t2b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pwm-t2b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:image-broken" {...props}></Icon>
