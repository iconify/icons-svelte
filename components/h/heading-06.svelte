<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7iybb6bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7iybb6bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heading-06" {...props}></Icon>
