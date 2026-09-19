<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns3l64bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns3l64bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ls-spot-iris-group-v2" {...props}></Icon>
