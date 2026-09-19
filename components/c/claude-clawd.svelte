<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pggf_ba-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pggf_ba-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:claude-clawd" {...props}></Icon>
