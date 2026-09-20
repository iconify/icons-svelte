<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp-vsxb4f.css';
import '../../css/w/ws9x54gvl.css';
import '../../css/v/vm_hfeb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-vsxb4f"/><path class="ws9x54gvl"/><path class="vm_hfeb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rhel-light" {...props}></Icon>
