<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt_7jqbdu.css';
import '../../css/b/b96vt-g1e.css';
import '../../css/l/l78zzhbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dt_7jqbdu"/><path class="b96vt-g1e"/><path class="l78zzhbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:leafwiki-light" {...props}></Icon>
