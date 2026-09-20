<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6hubzd-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6hubzd-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-chevrons-right-filled" {...props}></Icon>
