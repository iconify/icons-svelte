<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uum2aj53r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uum2aj53r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:facebook-gaming" {...props}></Icon>
