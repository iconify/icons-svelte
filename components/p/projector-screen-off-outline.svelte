<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fws7slz-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fws7slz-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:projector-screen-off-outline" {...props}></Icon>
