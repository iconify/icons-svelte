<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d44koac3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d44koac3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kde-neon" {...props}></Icon>
