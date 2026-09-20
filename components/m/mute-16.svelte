<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw3n3ty8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sw3n3ty8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mute-16" {...props}></Icon>
