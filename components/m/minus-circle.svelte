<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaqkji9ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iaqkji9ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:minus-circle" {...props}></Icon>
