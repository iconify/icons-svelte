<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utdbd58xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utdbd58xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:puzzle-edit-outline" {...props}></Icon>
