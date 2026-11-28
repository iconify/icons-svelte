<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-_-k6yqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-_-k6yqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:christmas-tree" {...props}></Icon>
