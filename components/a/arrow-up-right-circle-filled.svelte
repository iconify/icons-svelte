<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4jzyo9_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4jzyo9_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-right-circle-filled" {...props}></Icon>
