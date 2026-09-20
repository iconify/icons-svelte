<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exv1xebfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="exv1xebfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-text-alt-outline" {...props}></Icon>
