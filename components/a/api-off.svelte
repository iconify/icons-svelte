<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5klrkbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5klrkbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:api-off" {...props}></Icon>
