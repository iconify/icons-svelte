<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_fpo-b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c_fpo-b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:round-pushpin-small-filled" {...props}></Icon>
