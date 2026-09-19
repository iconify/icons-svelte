<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjcl_bc7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qjcl_bc7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:app-store" {...props}></Icon>
