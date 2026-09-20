<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhp05tb6w.css';
import '../../css/j/j2qm6zb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bhp05tb6w"/><path class="j2qm6zb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:globaleaks" {...props}></Icon>
