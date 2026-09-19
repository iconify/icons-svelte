<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvf-h2b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wvf-h2b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:boy-filled" {...props}></Icon>
