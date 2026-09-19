<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de3zcmpjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="de3zcmpjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleloaderfive" {...props}></Icon>
