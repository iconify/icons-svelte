<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxid1c1jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxid1c1jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:contract-check" {...props}></Icon>
