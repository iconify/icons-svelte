<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trz3lobaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trz3lobaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codeproject" {...props}></Icon>
