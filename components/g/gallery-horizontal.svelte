<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1u7v3b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1u7v3b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gallery-horizontal" {...props}></Icon>
