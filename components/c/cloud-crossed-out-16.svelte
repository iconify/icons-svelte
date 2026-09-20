<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh4yl5yun.css';
import '../../css/i/i8ocx-9hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rh4yl5yun"/><path class="i8ocx-9hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cloud-crossed-out-16" {...props}></Icon>
