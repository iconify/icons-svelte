<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcjmxnbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcjmxnbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:beats" {...props}></Icon>
