<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prd1j7b1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prd1j7b1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-maximise-outline" {...props}></Icon>
