<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwo8fybtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dwo8fybtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:apple-filled" {...props}></Icon>
