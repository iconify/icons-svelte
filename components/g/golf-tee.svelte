<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtv-78cph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtv-78cph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:golf-tee" {...props}></Icon>
