<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-rtspsnc.css';
import '../../css/o/owdlqbbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="l-rtspsnc"/><path class="owdlqbbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:quote-fill-12" {...props}></Icon>
