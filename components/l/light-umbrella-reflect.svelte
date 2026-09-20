<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj8_542oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj8_542oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:light-umbrella-reflect" {...props}></Icon>
