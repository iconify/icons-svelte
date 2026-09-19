<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6sim5rjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6sim5rjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-signal-2" {...props}></Icon>
