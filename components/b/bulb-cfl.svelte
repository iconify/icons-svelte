<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pawdocb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pawdocb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bulb-cfl" {...props}></Icon>
