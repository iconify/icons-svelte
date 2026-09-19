<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr3fmtb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fr3fmtb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:camera" {...props}></Icon>
