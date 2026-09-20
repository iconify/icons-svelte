<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6gkzsbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e6gkzsbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-no-access-outline" {...props}></Icon>
