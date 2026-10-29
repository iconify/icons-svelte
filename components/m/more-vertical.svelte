<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suqo8hbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suqo8hbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:more-vertical" {...props}></Icon>
