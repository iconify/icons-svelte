<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m77m-bb1r.css';
import '../../css/f/f5bqv3-2b.css';
import '../../css/b/bx2p6cc8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m77m-bb1r"/><path class="f5bqv3-2b"/><path class="bx2p6cc8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-alert-48" {...props}></Icon>
