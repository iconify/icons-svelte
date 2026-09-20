<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx7_a-boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx7_a-boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nextcloud" {...props}></Icon>
