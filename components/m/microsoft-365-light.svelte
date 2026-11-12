<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-vaxx0ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-vaxx0ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-365-light" {...props}></Icon>
