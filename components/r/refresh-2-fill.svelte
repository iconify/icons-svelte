<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0aej-r8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0aej-r8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-2-fill" {...props}></Icon>
