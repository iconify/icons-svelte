<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd1as4bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd1as4bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bowl-outline" {...props}></Icon>
