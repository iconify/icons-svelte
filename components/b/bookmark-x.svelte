<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9kt7zn7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9kt7zn7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookmark-x" {...props}></Icon>
