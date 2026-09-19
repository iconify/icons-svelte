<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wahv08b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wahv08b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:figma" {...props}></Icon>
