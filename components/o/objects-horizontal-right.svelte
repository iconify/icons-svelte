<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgosjybmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgosjybmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:objects-horizontal-right" {...props}></Icon>
