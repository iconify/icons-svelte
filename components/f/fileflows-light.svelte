<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwad2ux7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wwad2ux7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fileflows-light" {...props}></Icon>
