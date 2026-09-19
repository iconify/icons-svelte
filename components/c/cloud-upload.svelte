<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp65h5bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xp65h5bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:cloud-upload" {...props}></Icon>
