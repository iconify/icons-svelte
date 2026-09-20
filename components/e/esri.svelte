<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ely61vbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ely61vbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:esri" {...props}></Icon>
