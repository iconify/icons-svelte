<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnyvjw2vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnyvjw2vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:kids-room" {...props}></Icon>
