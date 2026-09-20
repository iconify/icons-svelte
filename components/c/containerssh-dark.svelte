<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb5bgx25v.css';
import '../../css/a/az6xitzef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wb5bgx25v"/><path class="az6xitzef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:containerssh-dark" {...props}></Icon>
