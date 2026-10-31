<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu791xb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu791xb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:feather-fill-round" {...props}></Icon>
