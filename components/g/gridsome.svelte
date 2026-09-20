<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxf25wbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxf25wbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gridsome" {...props}></Icon>
