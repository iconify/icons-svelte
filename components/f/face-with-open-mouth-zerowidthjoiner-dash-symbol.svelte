<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixi_e8amv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ixi_e8amv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:face-with-open-mouth-zerowidthjoiner-dash-symbol" {...props}></Icon>
