<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnd-vrqvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jnd-vrqvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-remove-fill" {...props}></Icon>
