<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmmcl_mnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmmcl_mnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:fishes" {...props}></Icon>
