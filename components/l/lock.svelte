<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iduj7sbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iduj7sbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:lock" {...props}></Icon>
