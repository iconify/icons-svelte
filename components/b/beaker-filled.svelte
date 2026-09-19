<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gap8vwbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gap8vwbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:beaker-filled" {...props}></Icon>
