<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrzugtb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrzugtb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bucket" {...props}></Icon>
