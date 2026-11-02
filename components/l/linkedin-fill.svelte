<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8zvq0pym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8zvq0pym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:linkedin-fill" {...props}></Icon>
