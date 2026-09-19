<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a87vvobix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a87vvobix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-snow" {...props}></Icon>
