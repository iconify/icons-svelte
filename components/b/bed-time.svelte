<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o35s1tbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o35s1tbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bed-time" {...props}></Icon>
