<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti6iz-nxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti6iz-nxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:clever-cloud" {...props}></Icon>
