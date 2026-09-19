<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbpsy19-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="mbpsy19-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:folder" {...props}></Icon>
