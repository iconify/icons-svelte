<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iitdx4b4n.css';
import '../../css/e/egm87yb8i.css';
import '../../css/o/oen_blbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iitdx4b4n"/><path class="egm87yb8i"/><path class="oen_blbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-monitor-light" {...props}></Icon>
