<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_zb0x5py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_zb0x5py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:house-user" {...props}></Icon>
