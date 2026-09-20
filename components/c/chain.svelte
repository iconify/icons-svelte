<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnxfqpbmo.css';
import '../../css/r/rv1y__2ie.css';
import '../../css/u/uoqs5ac6i.css';
import '../../css/d/d6-s8fbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fnxfqpbmo"/><path clip-rule="evenodd" class="rv1y__2ie"/><path class="uoqs5ac6i"/><path class="d6-s8fbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:chain" {...props}></Icon>
