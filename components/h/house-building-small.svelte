<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh9zjpb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fh9zjpb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:house-building-small" {...props}></Icon>
