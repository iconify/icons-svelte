<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htlaqcb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htlaqcb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:cbs-sports-alt" {...props}></Icon>
