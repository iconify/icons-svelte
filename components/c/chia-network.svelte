<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2imh-b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2imh-b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chia-network" {...props}></Icon>
