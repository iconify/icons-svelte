<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st78s92ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st78s92ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cart" {...props}></Icon>
