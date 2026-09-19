<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptle577jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptle577jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:metv" {...props}></Icon>
