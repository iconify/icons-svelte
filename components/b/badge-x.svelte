<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udt21abpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udt21abpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:badge-x" {...props}></Icon>
