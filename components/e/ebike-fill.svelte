<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c26hmkboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c26hmkboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ebike-fill" {...props}></Icon>
