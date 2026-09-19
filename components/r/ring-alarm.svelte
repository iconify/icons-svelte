<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asi6pxbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asi6pxbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ring-alarm" {...props}></Icon>
