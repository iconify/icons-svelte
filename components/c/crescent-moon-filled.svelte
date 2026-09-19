<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4qznv4lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f4qznv4lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:crescent-moon-filled" {...props}></Icon>
