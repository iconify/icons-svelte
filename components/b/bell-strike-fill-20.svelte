<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2we-hbpo.css';
import '../../css/b/bd2w689nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z2we-hbpo"/><path class="bd2w689nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bell-strike-fill-20" {...props}></Icon>
