<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii-15nbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii-15nbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:add-circle-fill" {...props}></Icon>
