<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on5x2sbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on5x2sbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:peerlist" {...props}></Icon>
