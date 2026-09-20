<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifjtf2bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifjtf2bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-messages" {...props}></Icon>
