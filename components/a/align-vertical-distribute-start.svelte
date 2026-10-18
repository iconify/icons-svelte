<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-2k4oiuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-2k4oiuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-vertical-distribute-start" {...props}></Icon>
