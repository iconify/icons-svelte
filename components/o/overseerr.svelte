<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci5w0x1se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci5w0x1se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:overseerr" {...props}></Icon>
