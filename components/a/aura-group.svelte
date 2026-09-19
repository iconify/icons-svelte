<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpyseabnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpyseabnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aura-group" {...props}></Icon>
