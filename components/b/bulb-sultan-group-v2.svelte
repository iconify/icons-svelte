<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th28v3ozw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th28v3ozw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-sultan-group-v2" {...props}></Icon>
