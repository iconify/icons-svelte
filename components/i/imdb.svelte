<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mds8r6baq.css';
import '../../css/d/d18mv78yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mds8r6baq"/><path class="d18mv78yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:imdb" {...props}></Icon>
