<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-mmimb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d-mmimb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-arrow-circled-small-filled" {...props}></Icon>
