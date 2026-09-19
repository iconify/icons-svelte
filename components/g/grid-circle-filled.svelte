<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3gp-eb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3gp-eb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-circle-filled" {...props}></Icon>
