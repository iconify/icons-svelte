<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rue6bqb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rue6bqb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:pill-filled" {...props}></Icon>
