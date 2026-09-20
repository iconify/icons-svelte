<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqo6g6brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqo6g6brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:label-percent" {...props}></Icon>
