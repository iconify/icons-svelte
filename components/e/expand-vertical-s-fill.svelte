<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0oikac5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0oikac5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-vertical-s-fill" {...props}></Icon>
