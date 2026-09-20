<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei9a25xnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ei9a25xnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:direction" {...props}></Icon>
