<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovsu6pbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":458,"height":96};
const content = `<path class="ovsu6pbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deskera" {...props}></Icon>
