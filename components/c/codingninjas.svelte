<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9f7o2fne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9f7o2fne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:codingninjas" {...props}></Icon>
