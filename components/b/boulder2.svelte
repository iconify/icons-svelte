<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akbufqbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="akbufqbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:boulder2" {...props}></Icon>
