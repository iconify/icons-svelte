<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ra722lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ra722lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-round-bottom-empty" {...props}></Icon>
