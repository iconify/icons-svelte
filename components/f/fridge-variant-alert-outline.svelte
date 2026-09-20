<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9hj4k0kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9hj4k0kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-variant-alert-outline" {...props}></Icon>
