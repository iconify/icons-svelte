<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3l2pb3_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3l2pb3_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:phone-gloss" {...props}></Icon>
