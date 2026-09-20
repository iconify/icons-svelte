<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvk7_6bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvk7_6bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:camera3-filled" {...props}></Icon>
