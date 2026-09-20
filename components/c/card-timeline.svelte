<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu9d84atf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="yu9d84atf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:card-timeline" {...props}></Icon>
