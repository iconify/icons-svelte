<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxyxf87ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vxyxf87ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:restroom-small-filled" {...props}></Icon>
