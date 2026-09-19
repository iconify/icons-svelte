<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cantnxqek.css';
import '../../css/a/aodxntc9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cantnxqek"/><path class="aodxntc9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-import" {...props}></Icon>
