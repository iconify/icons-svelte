<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujd98nbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujd98nbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:microwave-play" {...props}></Icon>
