<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy931_b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy931_b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pixelfed-line" {...props}></Icon>
