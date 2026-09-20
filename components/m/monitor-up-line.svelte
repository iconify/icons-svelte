<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0po_6bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0po_6bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-up-line" {...props}></Icon>
