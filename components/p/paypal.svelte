<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsk9izbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsk9izbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:paypal" {...props}></Icon>
