<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg0betbhc.css';
import '../../css/d/ddgckv3ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg0betbhc"/><rect class="ddgckv3ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:queue" {...props}></Icon>
