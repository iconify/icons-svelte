<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmh2ek7ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="bmh2ek7ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face6-small" {...props}></Icon>
