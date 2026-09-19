<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4vtj4tvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4vtj4tvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bridge" {...props}></Icon>
