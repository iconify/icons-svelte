<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewinqubjx.css';
import '../../css/j/js6qhmbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ewinqubjx"/><path class="js6qhmbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dailytxt" {...props}></Icon>
