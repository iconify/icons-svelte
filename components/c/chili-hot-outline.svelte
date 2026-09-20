<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haue8ibef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haue8ibef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chili-hot-outline" {...props}></Icon>
