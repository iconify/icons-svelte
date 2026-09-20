<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swz-qybok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="swz-qybok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-waning-crescent-3" {...props}></Icon>
