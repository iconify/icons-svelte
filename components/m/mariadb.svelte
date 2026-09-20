<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1og6cbek.css';
import '../../css/b/bh-4vfbma.css';
import '../../css/u/u5e77cb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p1og6cbek"/><path class="bh-4vfbma"/><path clip-rule="evenodd" class="u5e77cb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mariadb" {...props}></Icon>
