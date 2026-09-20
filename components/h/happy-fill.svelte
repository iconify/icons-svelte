<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elqg70krt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elqg70krt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:happy-fill" {...props}></Icon>
