<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc5_a1ncx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="oc5_a1ncx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:close-small" {...props}></Icon>
