<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un8-nx_wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1408};
const content = `<path class="un8-nx_wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hand-grab-o" {...props}></Icon>
