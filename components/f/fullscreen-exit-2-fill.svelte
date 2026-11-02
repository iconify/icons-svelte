<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygrgegf7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygrgegf7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fullscreen-exit-2-fill" {...props}></Icon>
