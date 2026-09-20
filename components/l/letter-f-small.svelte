<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og5hd0y1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og5hd0y1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-f-small" {...props}></Icon>
