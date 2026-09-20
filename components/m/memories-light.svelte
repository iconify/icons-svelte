<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok6uxj9nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ok6uxj9nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:memories-light" {...props}></Icon>
