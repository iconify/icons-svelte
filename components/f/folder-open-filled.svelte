<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqrwg2b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqrwg2b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-open-filled" {...props}></Icon>
