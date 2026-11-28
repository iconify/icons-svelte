<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuaq-1b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuaq-1b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:juice-box" {...props}></Icon>
