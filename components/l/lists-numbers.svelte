<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk8_q-b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk8_q-b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:lists-numbers" {...props}></Icon>
