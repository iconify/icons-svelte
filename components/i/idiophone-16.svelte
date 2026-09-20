<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbwe7mc1r.css';
import '../../css/k/kj3l2zbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fbwe7mc1r"/><path class="kj3l2zbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:idiophone-16" {...props}></Icon>
