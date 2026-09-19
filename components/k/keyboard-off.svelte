<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxc5sxbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rxc5sxbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:keyboard-off" {...props}></Icon>
