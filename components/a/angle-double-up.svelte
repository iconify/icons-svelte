<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo4avb77y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1280};
const content = `<path class="bo4avb77y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:angle-double-up" {...props}></Icon>
