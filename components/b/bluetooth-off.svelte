<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcdy78bcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pcdy78bcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bluetooth-off" {...props}></Icon>
