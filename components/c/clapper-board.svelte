<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv6_41bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tv6_41bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:clapper-board" {...props}></Icon>
