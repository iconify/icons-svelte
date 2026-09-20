<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiif26bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiif26bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-socket-de" {...props}></Icon>
