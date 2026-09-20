<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5dc8kbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5dc8kbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:lyn" {...props}></Icon>
