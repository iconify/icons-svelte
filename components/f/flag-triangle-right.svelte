<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm-xv_9uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm-xv_9uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:flag-triangle-right" {...props}></Icon>
