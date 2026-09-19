<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa212acpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa212acpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:apple-airpods" {...props}></Icon>
