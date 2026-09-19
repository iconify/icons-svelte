<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-b3v2tyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g-b3v2tyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:crescent-moon-small-filled" {...props}></Icon>
