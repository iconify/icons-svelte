<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awjydpnfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awjydpnfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jest" {...props}></Icon>
