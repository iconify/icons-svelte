<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw005s6mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw005s6mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-cashapp" {...props}></Icon>
