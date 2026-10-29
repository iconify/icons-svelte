<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqj8zfbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqj8zfbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:minus-duo" {...props}></Icon>
