<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnh3-2b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnh3-2b2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-long-fill" {...props}></Icon>
