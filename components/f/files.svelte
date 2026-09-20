<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbtsfbb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gbtsfbb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:files" {...props}></Icon>
