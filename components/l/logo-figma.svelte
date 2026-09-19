<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9a81jbes.css';
import '../../css/e/efn4s4b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r9a81jbes"/><circle class="efn4s4b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-figma" {...props}></Icon>
