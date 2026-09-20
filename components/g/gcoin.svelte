<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r68agabnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r68agabnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gcoin" {...props}></Icon>
