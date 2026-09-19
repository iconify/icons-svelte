<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqzifl2_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cqzifl2_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-then-curving-down-arrow-small" {...props}></Icon>
