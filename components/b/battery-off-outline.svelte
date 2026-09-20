<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk7xxcchg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk7xxcchg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-off-outline" {...props}></Icon>
