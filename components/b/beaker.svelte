<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygjv6qutr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ygjv6qutr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:beaker" {...props}></Icon>
