<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zozeas57z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zozeas57z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-bolt" {...props}></Icon>
