<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca-ltmebp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca-ltmebp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-40-bluetooth" {...props}></Icon>
