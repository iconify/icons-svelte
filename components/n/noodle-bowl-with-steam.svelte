<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diraqp4hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="diraqp4hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:noodle-bowl-with-steam" {...props}></Icon>
