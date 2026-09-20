<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl7v89b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nl7v89b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-access-2000-dark" {...props}></Icon>
