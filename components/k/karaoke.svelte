<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upa3gv_wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="upa3gv_wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:karaoke" {...props}></Icon>
