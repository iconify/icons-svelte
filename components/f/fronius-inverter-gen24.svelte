<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rteos1-3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rteos1-3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fronius-inverter-gen24" {...props}></Icon>
