<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcbrlz6ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcbrlz6ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:insert-column-left" {...props}></Icon>
