<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlpqn8a0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlpqn8a0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-4-fill" {...props}></Icon>
