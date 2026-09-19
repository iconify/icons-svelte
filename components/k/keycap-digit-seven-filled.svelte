<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c96ozvl4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c96ozvl4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-seven-filled" {...props}></Icon>
