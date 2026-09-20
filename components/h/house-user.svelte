<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc5dnkb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc5dnkb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:house-user" {...props}></Icon>
