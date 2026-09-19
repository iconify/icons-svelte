<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxhb4cbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oxhb4cbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:label-filled" {...props}></Icon>
