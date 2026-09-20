<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6lnhy9hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j6lnhy9hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:claude-light" {...props}></Icon>
