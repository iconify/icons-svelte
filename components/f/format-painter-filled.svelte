<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmue_db-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lmue_db-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:format-painter-filled" {...props}></Icon>
