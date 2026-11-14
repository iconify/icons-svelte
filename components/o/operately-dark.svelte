<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw8tm-bwd.css';
import '../../css/u/u-8cambew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pw8tm-bwd"/><path class="u-8cambew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:operately-dark" {...props}></Icon>
