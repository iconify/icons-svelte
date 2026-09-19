<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwmjj80ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwmjj80ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:music-alt-outline" {...props}></Icon>
