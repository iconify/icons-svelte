<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojv9pubkm.css';
import '../../css/h/hur7hdsnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojv9pubkm"/><path class="hur7hdsnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pizza-alt-filled" {...props}></Icon>
