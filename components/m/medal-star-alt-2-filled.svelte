<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y64_zlase.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y64_zlase"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medal-star-alt-2-filled" {...props}></Icon>
