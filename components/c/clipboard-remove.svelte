<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu9gzib2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu9gzib2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-remove" {...props}></Icon>
