<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovxvs_b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovxvs_b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:p2p-fill" {...props}></Icon>
