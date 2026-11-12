<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo0jstbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zo0jstbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-copilot-dark" {...props}></Icon>
