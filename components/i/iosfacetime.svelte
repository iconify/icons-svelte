<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j60i7hb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j60i7hb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:iosfacetime" {...props}></Icon>
