<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5w2sby7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5w2sby7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-filled" {...props}></Icon>
