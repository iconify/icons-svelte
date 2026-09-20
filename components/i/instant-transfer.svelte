<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smj6sg1pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smj6sg1pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:instant-transfer" {...props}></Icon>
