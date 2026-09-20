<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di13lq8_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di13lq8_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bower" {...props}></Icon>
