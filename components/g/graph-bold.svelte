<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9t0g5brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9t0g5brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:graph-bold" {...props}></Icon>
