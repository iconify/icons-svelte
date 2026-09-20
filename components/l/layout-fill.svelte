<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx1rnpmkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx1rnpmkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-fill" {...props}></Icon>
