<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx5tgy66g.css';
import '../../css/g/gx3qh1bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kx5tgy66g"/><path class="gx3qh1bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:buffer-16" {...props}></Icon>
