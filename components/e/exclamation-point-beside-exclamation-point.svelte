<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai-hwv_fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ai-hwv_fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:exclamation-point-beside-exclamation-point" {...props}></Icon>
