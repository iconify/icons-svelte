<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0lir1lzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0lir1lzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cry-and-laugh-filled" {...props}></Icon>
