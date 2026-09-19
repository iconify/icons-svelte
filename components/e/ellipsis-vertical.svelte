<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucrnmccuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucrnmccuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ellipsis-vertical" {...props}></Icon>
