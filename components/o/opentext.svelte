<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooev40plq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooev40plq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opentext" {...props}></Icon>
