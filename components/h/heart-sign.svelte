<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc8mccbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc8mccbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:heart-sign" {...props}></Icon>
