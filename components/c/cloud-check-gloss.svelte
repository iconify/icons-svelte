<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o65s5dbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o65s5dbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-check-gloss" {...props}></Icon>
