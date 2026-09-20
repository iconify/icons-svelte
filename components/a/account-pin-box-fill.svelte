<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky5j3dbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky5j3dbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:account-pin-box-fill" {...props}></Icon>
