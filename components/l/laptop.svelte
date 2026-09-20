<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylg5d7dup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylg5d7dup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:laptop" {...props}></Icon>
