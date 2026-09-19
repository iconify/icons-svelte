<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0m4rffbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0m4rffbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:git" {...props}></Icon>
