<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd-dy5b1v.css';
import '../../css/m/m3911cl6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cd-dy5b1v"/><path class="m3911cl6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-storage-bold-duotone" {...props}></Icon>
