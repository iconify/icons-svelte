<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikkzycc1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikkzycc1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:private-internet-access" {...props}></Icon>
