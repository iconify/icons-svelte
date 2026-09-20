<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybzysccdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybzysccdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:instructure" {...props}></Icon>
