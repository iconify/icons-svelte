<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzuu4u4mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzuu4u4mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-heart-filled" {...props}></Icon>
