<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rowc7b8ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rowc7b8ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kodular" {...props}></Icon>
