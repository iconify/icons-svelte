<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ompke7h3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ompke7h3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gallery-vertical-end" {...props}></Icon>
