<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc6hhsb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uc6hhsb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-axes-2d" {...props}></Icon>
