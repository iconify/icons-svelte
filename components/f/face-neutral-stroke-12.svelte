<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyuyv9n9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vyuyv9n9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:face-neutral-stroke-12" {...props}></Icon>
