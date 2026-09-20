<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsrkp8q7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsrkp8q7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:coffee-filled" {...props}></Icon>
