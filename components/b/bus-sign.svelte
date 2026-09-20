<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikk0jabqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikk0jabqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bus-sign" {...props}></Icon>
