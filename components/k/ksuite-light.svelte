<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivc1utbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ivc1utbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-light" {...props}></Icon>
