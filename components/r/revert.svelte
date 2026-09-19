<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duiy32tko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="duiy32tko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:revert" {...props}></Icon>
