<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbxbsj5py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbxbsj5py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:event-remove-outline" {...props}></Icon>
