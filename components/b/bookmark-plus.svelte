<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4f6jzb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4f6jzb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-plus" {...props}></Icon>
