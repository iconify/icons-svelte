<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwm12xbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwm12xbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:message" {...props}></Icon>
