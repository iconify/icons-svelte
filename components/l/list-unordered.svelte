<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkgq6cbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mkgq6cbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:list-unordered" {...props}></Icon>
