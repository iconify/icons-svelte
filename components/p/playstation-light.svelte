<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfu2lbbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qfu2lbbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:playstation-light" {...props}></Icon>
