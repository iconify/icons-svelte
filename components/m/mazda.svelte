<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0ad9xbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0ad9xbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mazda" {...props}></Icon>
