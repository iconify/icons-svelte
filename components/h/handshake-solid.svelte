<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of_bt5blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of_bt5blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:handshake-solid" {...props}></Icon>
