<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnnlgvb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jnnlgvb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:high-speed-train" {...props}></Icon>
