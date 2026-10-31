<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibho_3u6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibho_3u6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-letter-t" {...props}></Icon>
