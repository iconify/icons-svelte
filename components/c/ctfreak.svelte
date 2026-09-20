<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phezrpb0j.css';
import '../../css/r/rbhs_9jqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="phezrpb0j"/><path class="rbhs_9jqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ctfreak" {...props}></Icon>
