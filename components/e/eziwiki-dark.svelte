<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppk4v-xzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ppk4v-xzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eziwiki-dark" {...props}></Icon>
