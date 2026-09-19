<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugzzx9ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugzzx9ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bluetooth-filled" {...props}></Icon>
