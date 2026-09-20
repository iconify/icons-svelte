<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heccx78bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="heccx78bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:medassist-light" {...props}></Icon>
