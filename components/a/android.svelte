<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx8lp924d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx8lp924d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:android" {...props}></Icon>
