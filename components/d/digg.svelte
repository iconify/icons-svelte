<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rog9c546b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rog9c546b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:digg" {...props}></Icon>
