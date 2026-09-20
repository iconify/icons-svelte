<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1m6v99mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1m6v99mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-bolt" {...props}></Icon>
