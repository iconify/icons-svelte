<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qapb64bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qapb64bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:bell-slash" {...props}></Icon>
