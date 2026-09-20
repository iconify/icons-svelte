<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5jgz3bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5jgz3bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:envelope-lock" {...props}></Icon>
