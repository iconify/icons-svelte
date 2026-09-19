<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkin46bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkin46bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:iossettings" {...props}></Icon>
