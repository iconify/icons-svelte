<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2p_948kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2p_948kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:checkmk" {...props}></Icon>
