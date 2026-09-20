<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xei1q935s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xei1q935s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pythonanywhere" {...props}></Icon>
