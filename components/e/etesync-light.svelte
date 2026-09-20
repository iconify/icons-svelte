<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x98thzm6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x98thzm6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:etesync-light" {...props}></Icon>
