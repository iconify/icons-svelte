<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u22te8bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u22te8bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:omnipoly" {...props}></Icon>
