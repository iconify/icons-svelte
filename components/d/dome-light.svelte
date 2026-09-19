<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps25r6b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps25r6b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dome-light" {...props}></Icon>
