<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzw0sac3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zzw0sac3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coder-dark" {...props}></Icon>
