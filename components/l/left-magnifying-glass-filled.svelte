<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjs3ttbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cjs3ttbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:left-magnifying-glass-filled" {...props}></Icon>
