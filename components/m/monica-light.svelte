<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd_clobel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nd_clobel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:monica-light" {...props}></Icon>
