<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kln6l2-vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kln6l2-vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-outline" {...props}></Icon>
