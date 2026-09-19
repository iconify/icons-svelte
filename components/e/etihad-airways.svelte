<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxqn-s10j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxqn-s10j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:etihad-airways" {...props}></Icon>
