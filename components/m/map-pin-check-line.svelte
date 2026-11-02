<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-hkubwta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-hkubwta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-check-line" {...props}></Icon>
