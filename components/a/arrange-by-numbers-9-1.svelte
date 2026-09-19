<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1g6zcb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1g6zcb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrange-by-numbers-9-1" {...props}></Icon>
