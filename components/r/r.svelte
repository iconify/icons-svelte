<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy062-bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy062-bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:r" {...props}></Icon>
