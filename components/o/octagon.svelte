<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei_3t-bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei_3t-bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:octagon" {...props}></Icon>
