<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdir-06ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdir-06ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-plus" {...props}></Icon>
