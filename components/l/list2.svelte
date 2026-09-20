<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm8cskzid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zm8cskzid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:list2" {...props}></Icon>
