<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flrk_ibxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flrk_ibxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:javascript-fill" {...props}></Icon>
