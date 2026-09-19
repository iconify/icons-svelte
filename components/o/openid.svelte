<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozdpp2avr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ozdpp2avr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:openid" {...props}></Icon>
