<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmlc4rbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lmlc4rbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:agregarr" {...props}></Icon>
