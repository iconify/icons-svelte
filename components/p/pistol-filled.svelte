<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pishw9bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pishw9bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pistol-filled" {...props}></Icon>
