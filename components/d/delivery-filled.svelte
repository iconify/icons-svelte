<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv86zo07c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nv86zo07c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:delivery-filled" {...props}></Icon>
