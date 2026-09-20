<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmdqljbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wmdqljbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:emergency-phone" {...props}></Icon>
