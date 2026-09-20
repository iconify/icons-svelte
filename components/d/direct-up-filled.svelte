<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8xv77byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8xv77byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:direct-up-filled" {...props}></Icon>
