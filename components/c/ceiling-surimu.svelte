<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el_u14isu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el_u14isu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-surimu" {...props}></Icon>
