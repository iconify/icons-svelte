<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b44s31boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="b44s31boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:blogger" {...props}></Icon>
