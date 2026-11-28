<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr0c4zexh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr0c4zexh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:monitor-play" {...props}></Icon>
