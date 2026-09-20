<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s73uwioim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s73uwioim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:circle-warning-filled" {...props}></Icon>
