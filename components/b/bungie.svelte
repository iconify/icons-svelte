<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi4a21e2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi4a21e2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bungie" {...props}></Icon>
