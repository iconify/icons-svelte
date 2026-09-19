<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo-95gboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zo-95gboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:hamburger" {...props}></Icon>
