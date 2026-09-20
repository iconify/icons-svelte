<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5aoxab8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5aoxab8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:divide-line" {...props}></Icon>
