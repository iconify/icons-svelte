<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pls3clwxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pls3clwxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:heart-add-2-fill" {...props}></Icon>
