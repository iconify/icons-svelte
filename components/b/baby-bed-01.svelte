<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtilukbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtilukbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:baby-bed-01" {...props}></Icon>
