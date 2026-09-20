<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z55t-is9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z55t-is9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:odnoklassniki" {...props}></Icon>
