<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6x4xva_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1792};
const content = `<path class="x6x4xva_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cutlery" {...props}></Icon>
