<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsp5zr9ng.css';
import '../../css/b/bbjq83b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nsp5zr9ng"/><path class="bbjq83b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailpit" {...props}></Icon>
