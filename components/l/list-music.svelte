<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbcdme82c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbcdme82c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:list-music" {...props}></Icon>
