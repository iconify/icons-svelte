<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-oiem-5f.css';
import '../../css/m/mw_3mdbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q-oiem-5f"/><path class="mw_3mdbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:call-hold-16" {...props}></Icon>
