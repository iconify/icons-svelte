<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnp3qpb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnp3qpb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:enpass" {...props}></Icon>
