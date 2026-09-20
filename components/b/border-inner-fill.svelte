<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu2di8bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu2di8bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-inner-fill" {...props}></Icon>
