<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbe5bub9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rbe5bub9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bell-filled" {...props}></Icon>
