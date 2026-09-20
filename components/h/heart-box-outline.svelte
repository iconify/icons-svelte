<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1t1-bcbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1t1-bcbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-box-outline" {...props}></Icon>
