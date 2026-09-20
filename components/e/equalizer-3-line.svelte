<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g98ny67fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g98ny67fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:equalizer-3-line" {...props}></Icon>
