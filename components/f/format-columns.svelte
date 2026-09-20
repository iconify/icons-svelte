<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx9-le8ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx9-le8ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-columns" {...props}></Icon>
