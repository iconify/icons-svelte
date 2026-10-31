<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oewq_tvoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oewq_tvoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:frown-gloss" {...props}></Icon>
