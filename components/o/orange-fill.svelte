<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq9qfd_rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uq9qfd_rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:orange-fill" {...props}></Icon>
