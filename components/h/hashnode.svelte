<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdp2_hgrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mdp2_hgrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:hashnode" {...props}></Icon>
