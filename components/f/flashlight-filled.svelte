<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by92ajukm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by92ajukm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:flashlight-filled" {...props}></Icon>
