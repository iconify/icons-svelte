<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykdfyfbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykdfyfbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dvd-line" {...props}></Icon>
