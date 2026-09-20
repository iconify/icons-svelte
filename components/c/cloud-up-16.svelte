<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmo45hhmm.css';
import '../../css/h/hb4vkiz6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tmo45hhmm"/><path class="hb4vkiz6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cloud-up-16" {...props}></Icon>
