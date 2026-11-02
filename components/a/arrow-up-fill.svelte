<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk7w4zbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk7w4zbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-fill" {...props}></Icon>
