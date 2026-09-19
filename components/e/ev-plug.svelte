<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1vzxi4tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1vzxi4tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ev-plug" {...props}></Icon>
