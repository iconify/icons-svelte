<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnf9xcxen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnf9xcxen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:moon-line" {...props}></Icon>
