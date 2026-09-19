<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soso3u_zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="soso3u_zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:reddit" {...props}></Icon>
