<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufzg5m6eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufzg5m6eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:laundry-room-alert" {...props}></Icon>
