<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4youg6gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4youg6gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:close-ring" {...props}></Icon>
