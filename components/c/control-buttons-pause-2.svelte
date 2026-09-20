<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5ousf9rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g5ousf9rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-pause-2" {...props}></Icon>
