<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u893fxc0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="u893fxc0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:graduation-cap" {...props}></Icon>
