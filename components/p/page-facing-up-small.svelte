<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8-wchbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="a8-wchbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:page-facing-up-small" {...props}></Icon>
