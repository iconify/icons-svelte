<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_3vepb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="e_3vepb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-text-alt-solid" {...props}></Icon>
