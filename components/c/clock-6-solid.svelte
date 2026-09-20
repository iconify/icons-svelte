<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-cfmzj2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-cfmzj2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:clock-6-solid" {...props}></Icon>
