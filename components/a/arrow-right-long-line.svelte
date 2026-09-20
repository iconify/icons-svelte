<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz0yvmeas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz0yvmeas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-long-line" {...props}></Icon>
