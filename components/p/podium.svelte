<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgu_3ibqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xgu_3ibqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:podium" {...props}></Icon>
