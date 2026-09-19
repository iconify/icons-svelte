<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6us18bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="p6us18bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:accordion" {...props}></Icon>
