<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb11dvb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb11dvb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nano-stores" {...props}></Icon>
