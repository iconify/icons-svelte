<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbbhirtib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbbhirtib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:alarm-snooze" {...props}></Icon>
