<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs2gjggro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs2gjggro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:plus-octagon-solid" {...props}></Icon>
