<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg5ix7bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg5ix7bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codesignal" {...props}></Icon>
