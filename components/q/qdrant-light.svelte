<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2gmwachp.css';
import '../../css/q/qs06oviiv.css';
import '../../css/l/lhdmhjbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u2gmwachp"/><path class="qs06oviiv"/><path class="lhdmhjbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qdrant-light" {...props}></Icon>
