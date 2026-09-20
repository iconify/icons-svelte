<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4l_n6szq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b4l_n6szq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:caret-vertical-solid" {...props}></Icon>
