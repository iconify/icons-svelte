<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz1n2pb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz1n2pb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:garage-open-variant" {...props}></Icon>
