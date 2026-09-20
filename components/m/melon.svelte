<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eho20050m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eho20050m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:melon" {...props}></Icon>
