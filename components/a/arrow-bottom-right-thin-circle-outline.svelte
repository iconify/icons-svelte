<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elwzyekta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elwzyekta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-right-thin-circle-outline" {...props}></Icon>
