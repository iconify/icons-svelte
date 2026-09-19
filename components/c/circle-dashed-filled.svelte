<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0x597vfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0x597vfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-dashed-filled" {...props}></Icon>
