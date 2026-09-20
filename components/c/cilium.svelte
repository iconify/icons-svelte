<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrml5ge7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrml5ge7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cilium" {...props}></Icon>
