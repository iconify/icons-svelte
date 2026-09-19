<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs0_786be.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xs0_786be"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:rabbit-face" {...props}></Icon>
