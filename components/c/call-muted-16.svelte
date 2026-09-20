<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2yet2bpf.css';
import '../../css/w/wn3ahbbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p2yet2bpf"/><path class="wn3ahbbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:call-muted-16" {...props}></Icon>
