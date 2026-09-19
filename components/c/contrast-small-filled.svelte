<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh_-wvb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rh_-wvb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:contrast-small-filled" {...props}></Icon>
