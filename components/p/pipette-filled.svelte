<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3mxc9bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3mxc9bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pipette-filled" {...props}></Icon>
