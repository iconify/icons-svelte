<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzag0q2pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vzag0q2pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pytest" {...props}></Icon>
