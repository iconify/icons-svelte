<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itx63nyal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itx63nyal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:loop-round" {...props}></Icon>
