<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0x80go8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0x80go8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:drag-vertical" {...props}></Icon>
