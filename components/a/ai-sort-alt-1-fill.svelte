<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqpo30-3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqpo30-3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-sort-alt-1-fill" {...props}></Icon>
