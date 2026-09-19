<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y19h4g-0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y19h4g-0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medal-alt-2-filled" {...props}></Icon>
