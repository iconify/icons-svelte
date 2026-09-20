<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8vvx1b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8vvx1b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home2-filled" {...props}></Icon>
