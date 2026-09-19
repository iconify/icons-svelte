<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2k3m0xzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h2k3m0xzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:petri-dish" {...props}></Icon>
