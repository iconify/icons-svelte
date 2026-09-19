<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwxhpy1gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwxhpy1gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lock" {...props}></Icon>
