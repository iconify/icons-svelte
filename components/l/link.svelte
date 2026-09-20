<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shc64lbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shc64lbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:link" {...props}></Icon>
