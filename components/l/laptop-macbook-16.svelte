<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr_nvx8tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xr_nvx8tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:laptop-macbook-16" {...props}></Icon>
