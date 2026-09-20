<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il9r52klx.css';
import '../../css/r/rlm82lo4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="il9r52klx"/><path class="rlm82lo4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-up-circle" {...props}></Icon>
