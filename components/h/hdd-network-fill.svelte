<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av81snbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="av81snbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hdd-network-fill" {...props}></Icon>
