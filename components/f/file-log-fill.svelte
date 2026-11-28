<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttjhitbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ttjhitbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-log-fill" {...props}></Icon>
