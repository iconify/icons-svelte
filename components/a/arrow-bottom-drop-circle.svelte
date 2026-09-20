<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwyhk3bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwyhk3bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-drop-circle" {...props}></Icon>
