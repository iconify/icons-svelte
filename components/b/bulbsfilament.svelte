<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyvt1zbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyvt1zbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulbsfilament" {...props}></Icon>
