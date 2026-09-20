<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mibhr1bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mibhr1bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grip-horizontal-fill" {...props}></Icon>
