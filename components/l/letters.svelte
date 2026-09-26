<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp4ubxbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp4ubxbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letters" {...props}></Icon>
