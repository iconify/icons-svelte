<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdhpbdb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdhpbdb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-vertical-space-around" {...props}></Icon>
