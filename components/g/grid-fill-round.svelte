<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnri7s2ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnri7s2ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:grid-fill-round" {...props}></Icon>
