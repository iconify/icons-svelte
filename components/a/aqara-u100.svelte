<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv5dp4p7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv5dp4p7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-u100" {...props}></Icon>
