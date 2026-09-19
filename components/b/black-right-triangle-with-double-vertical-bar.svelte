<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7p52cbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t7p52cbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-right-triangle-with-double-vertical-bar" {...props}></Icon>
