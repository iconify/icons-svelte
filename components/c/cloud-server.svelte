<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7-upabru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7-upabru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-server" {...props}></Icon>
