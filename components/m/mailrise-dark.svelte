<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2ds99bls.css';
import '../../css/y/yurlis35z.css';
import '../../css/b/b93z67b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v2ds99bls"/><path class="yurlis35z"/><path class="b93z67b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailrise-dark" {...props}></Icon>
