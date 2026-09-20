<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0dwpu11b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0dwpu11b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cake-2-line" {...props}></Icon>
