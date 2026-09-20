<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my8szwk-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my8szwk-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:elk" {...props}></Icon>
