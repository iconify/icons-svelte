<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdsbj4btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rdsbj4btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:bullhorn" {...props}></Icon>
