<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac1bsobcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":150,"height":512};
const content = `<path class="ac1bsobcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cwl" {...props}></Icon>
