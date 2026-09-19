<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf_avcpdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf_avcpdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-mid-snow" {...props}></Icon>
