<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7bywp-mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":740,"height":800};
const content = `<path class="h7bywp-mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:folder" {...props}></Icon>
