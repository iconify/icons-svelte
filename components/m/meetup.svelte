<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq32g6yaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="wq32g6yaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:meetup" {...props}></Icon>
