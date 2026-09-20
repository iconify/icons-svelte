<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2blhacbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2blhacbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:logout" {...props}></Icon>
