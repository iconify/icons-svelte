<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef767dm3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ef767dm3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:good-two" {...props}></Icon>
