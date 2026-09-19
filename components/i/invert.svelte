<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5s_1sbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a5s_1sbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:invert" {...props}></Icon>
