<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvd_t7aci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvd_t7aci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:lock" {...props}></Icon>
