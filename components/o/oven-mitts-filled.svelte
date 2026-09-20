<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5qa4em6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5qa4em6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:oven-mitts-filled" {...props}></Icon>
