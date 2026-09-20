<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_jbxs31n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_jbxs31n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kali-linux-dark" {...props}></Icon>
