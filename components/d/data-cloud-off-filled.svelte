<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wky75f0nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wky75f0nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:data-cloud-off-filled" {...props}></Icon>
