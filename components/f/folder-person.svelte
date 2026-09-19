<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd6pou8aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="yd6pou8aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:folder-person" {...props}></Icon>
