<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thjka7p4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="thjka7p4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:go-16" {...props}></Icon>
